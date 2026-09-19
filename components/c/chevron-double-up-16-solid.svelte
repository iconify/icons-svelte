<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mecs8xbyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mecs8xbyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-double-up-16-solid" {...props}></Icon>
