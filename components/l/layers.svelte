<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkg7e-bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="nkg7e-bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:layers" {...props}></Icon>
