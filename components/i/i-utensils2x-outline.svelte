<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gl4crjbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="gl4crjbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:i-utensils2x-outline" {...props}></Icon>
