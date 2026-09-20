<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_8fzr7kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k_8fzr7kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bluetooth" {...props}></Icon>
