<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqxt5mdob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cqxt5mdob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:github-fill" {...props}></Icon>
