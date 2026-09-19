<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4-ax83th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="c4-ax83th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:github-alt" {...props}></Icon>
