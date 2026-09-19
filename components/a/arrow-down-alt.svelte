<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkgito_qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jkgito_qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:arrow-down-alt" {...props}></Icon>
