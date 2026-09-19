<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk-r7jbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bk-r7jbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:cogs" {...props}></Icon>
