<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-be48n4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-be48n4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-merge-2-fill" {...props}></Icon>
