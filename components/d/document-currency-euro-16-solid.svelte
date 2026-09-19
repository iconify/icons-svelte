<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez4nq7t0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ez4nq7t0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-euro-16-solid" {...props}></Icon>
