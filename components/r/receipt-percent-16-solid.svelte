<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leera0b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="leera0b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:receipt-percent-16-solid" {...props}></Icon>
