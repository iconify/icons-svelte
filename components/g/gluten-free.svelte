<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv2qk8b_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lv2qk8b_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gluten-free" {...props}></Icon>
