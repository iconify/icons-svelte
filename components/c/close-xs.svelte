<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd0_zwbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="kd0_zwbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:close-xs" {...props}></Icon>
