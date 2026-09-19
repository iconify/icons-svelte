<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk_fp9bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jk_fp9bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:info" {...props}></Icon>
