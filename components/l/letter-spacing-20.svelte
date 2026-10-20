<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq0yvabzs.css';
import '../../css/u/ura9qubce.css';
import '../../css/u/ufqapwbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jq0yvabzs"/><path class="ura9qubce"/><path class="ufqapwbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:letter-spacing-20" {...props}></Icon>
