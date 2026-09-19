<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af2n3wb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="af2n3wb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:finger-print-16-solid" {...props}></Icon>
