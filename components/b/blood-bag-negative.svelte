<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j88ll_bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j88ll_bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-bag-negative" {...props}></Icon>
