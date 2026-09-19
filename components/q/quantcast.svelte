<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_zhne32i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e_zhne32i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:quantcast" {...props}></Icon>
