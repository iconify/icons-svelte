<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vipz4vb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vipz4vb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-branch-fill" {...props}></Icon>
