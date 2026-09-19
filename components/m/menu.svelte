<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyg_77bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hyg_77bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:menu" {...props}></Icon>
