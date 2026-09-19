<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7m911b_b.css';
import '../../css/j/jrn4e4b1s.css';
import '../../css/f/fxcjnopxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7m911b_b"/><path class="jrn4e4b1s"/><path class="fxcjnopxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-tennisball" {...props}></Icon>
