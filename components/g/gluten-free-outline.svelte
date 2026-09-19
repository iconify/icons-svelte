<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivpgmwkfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ivpgmwkfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gluten-free-outline" {...props}></Icon>
