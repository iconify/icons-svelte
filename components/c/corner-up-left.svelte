<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m843eubsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m843eubsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:corner-up-left" {...props}></Icon>
