<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4hcmvbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w4hcmvbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:puzzle" {...props}></Icon>
