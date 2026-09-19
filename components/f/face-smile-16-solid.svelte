<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec21vyzpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ec21vyzpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:face-smile-16-solid" {...props}></Icon>
