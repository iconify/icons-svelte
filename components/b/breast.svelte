<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyec7dodw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gyec7dodw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:breast" {...props}></Icon>
