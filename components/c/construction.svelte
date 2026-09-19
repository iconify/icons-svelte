<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7-7u_b9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="z7-7u_b9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:construction" {...props}></Icon>
