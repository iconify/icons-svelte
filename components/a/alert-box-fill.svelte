<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye9hi3bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ye9hi3bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alert-box-fill" {...props}></Icon>
