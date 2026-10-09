<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvx3ydb_k.css';
import '../../css/n/nov116bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nvx3ydb_k"/><path class="nov116bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hash-20-bold" {...props}></Icon>
