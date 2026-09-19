<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecnejhb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ecnejhb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-uturn-right-20-solid" {...props}></Icon>
