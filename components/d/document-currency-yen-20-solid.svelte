<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6ij-rbll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="d6ij-rbll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-yen-20-solid" {...props}></Icon>
