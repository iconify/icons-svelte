<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5j6imbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m5j6imbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:proselint" {...props}></Icon>
