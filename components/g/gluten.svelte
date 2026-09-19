<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_4zlfbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k_4zlfbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gluten" {...props}></Icon>
