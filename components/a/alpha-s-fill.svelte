<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6182vc9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="c6182vc9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-s-fill" {...props}></Icon>
