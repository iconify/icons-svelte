<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl06tlnfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="sl06tlnfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:contraceptive-patch" {...props}></Icon>
