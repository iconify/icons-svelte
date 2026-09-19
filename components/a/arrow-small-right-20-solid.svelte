<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k58n_0uxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k58n_0uxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-small-right-20-solid" {...props}></Icon>
