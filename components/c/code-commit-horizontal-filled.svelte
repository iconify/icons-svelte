<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypzkg3b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ypzkg3b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-commit-horizontal-filled" {...props}></Icon>
