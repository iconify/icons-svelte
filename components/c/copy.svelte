<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ughq2cbhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ughq2cbhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:copy" {...props}></Icon>
