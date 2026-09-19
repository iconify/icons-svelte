<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9gpahb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n9gpahb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-bangladeshi-16-solid" {...props}></Icon>
