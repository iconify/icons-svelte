<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcu0spkpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="dcu0spkpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:circle-grid-3x3-fill" {...props}></Icon>
