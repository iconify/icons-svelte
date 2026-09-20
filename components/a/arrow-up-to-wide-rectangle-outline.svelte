<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qidcoy8qd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qidcoy8qd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-up-to-wide-rectangle-outline" {...props}></Icon>
