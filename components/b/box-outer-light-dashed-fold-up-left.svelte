<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6r2qubzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="d6r2qubzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-dashed-fold-up-left" {...props}></Icon>
