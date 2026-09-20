<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp2s9rbkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tp2s9rbkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-merge-16" {...props}></Icon>
