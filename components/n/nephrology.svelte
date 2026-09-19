<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc7o-gtnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zc7o-gtnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:nephrology" {...props}></Icon>
