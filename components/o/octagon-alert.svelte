<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkr_chbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hkr_chbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:octagon-alert" {...props}></Icon>
