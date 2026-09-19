<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0i5ozbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h0i5ozbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:2-outline" {...props}></Icon>
