<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxd2nobky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxd2nobky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevron-left-sharp-fill" {...props}></Icon>
