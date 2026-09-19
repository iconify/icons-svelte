<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq-4ybc2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fq-4ybc2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-tsx" {...props}></Icon>
