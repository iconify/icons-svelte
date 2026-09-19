<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kejb9lbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kejb9lbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up-circle-16-solid" {...props}></Icon>
