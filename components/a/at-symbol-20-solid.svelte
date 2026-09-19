<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_jqjh0hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k_jqjh0hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:at-symbol-20-solid" {...props}></Icon>
