<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttbm51bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ttbm51bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-grid-2x2" {...props}></Icon>
