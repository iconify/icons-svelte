<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-1uf6h2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t-1uf6h2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-down-above-eight-one-one" {...props}></Icon>
