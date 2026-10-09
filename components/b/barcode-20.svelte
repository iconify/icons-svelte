<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuxhki93l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kuxhki93l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:barcode-20" {...props}></Icon>
