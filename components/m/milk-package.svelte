<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lru9cnbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lru9cnbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:milk-package" {...props}></Icon>
