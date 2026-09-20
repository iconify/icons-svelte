<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai_i-_rwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ai_i-_rwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:compass" {...props}></Icon>
