<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9mrh9bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="d9mrh9bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:health-data-security-outline" {...props}></Icon>
