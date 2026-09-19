<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhn23_shf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhn23_shf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:code-commit-vertical-filled" {...props}></Icon>
