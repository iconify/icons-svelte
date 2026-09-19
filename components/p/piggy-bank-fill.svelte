<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm3iwqbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gm3iwqbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:piggy-bank-fill" {...props}></Icon>
