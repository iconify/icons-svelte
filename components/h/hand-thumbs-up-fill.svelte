<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkk31pxxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kkk31pxxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hand-thumbs-up-fill" {...props}></Icon>
