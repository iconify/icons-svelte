<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sos5epbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sos5epbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:maximize-20" {...props}></Icon>
