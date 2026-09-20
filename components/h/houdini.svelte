<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv9tkk43r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv9tkk43r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:houdini" {...props}></Icon>
