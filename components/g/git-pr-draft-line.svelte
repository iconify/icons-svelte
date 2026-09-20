<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1rfu0b2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1rfu0b2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-pr-draft-line" {...props}></Icon>
