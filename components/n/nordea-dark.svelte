<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czvq_1biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1515,"height":1477};
const content = `<path class="czvq_1biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nordea-dark" {...props}></Icon>
