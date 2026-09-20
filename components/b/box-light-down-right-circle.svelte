<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctet27sra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ctet27sra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-down-right-circle" {...props}></Icon>
