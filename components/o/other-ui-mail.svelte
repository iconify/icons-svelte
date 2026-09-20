<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4bwg2bvq.css';
import '../../css/y/y7jxbyb3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y4bwg2bvq"/><path class="y7jxbyb3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-mail" {...props}></Icon>
