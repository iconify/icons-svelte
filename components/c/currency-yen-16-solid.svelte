<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5bz3lbad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s5bz3lbad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:currency-yen-16-solid" {...props}></Icon>
