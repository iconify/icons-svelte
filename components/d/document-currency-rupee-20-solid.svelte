<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5zexx5pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l5zexx5pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-rupee-20-solid" {...props}></Icon>
