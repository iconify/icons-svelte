<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc459gpon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zc459gpon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:liver-alt-outline" {...props}></Icon>
