<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9frxobaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q9frxobaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-call" {...props}></Icon>
