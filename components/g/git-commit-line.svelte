<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itz2mac9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itz2mac9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-commit-line" {...props}></Icon>
