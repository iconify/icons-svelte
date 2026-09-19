<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnaxm_n2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="nnaxm_n2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:number-square-fill" {...props}></Icon>
