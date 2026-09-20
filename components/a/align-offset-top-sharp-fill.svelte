<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk459lnoe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk459lnoe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-top-sharp-fill" {...props}></Icon>
