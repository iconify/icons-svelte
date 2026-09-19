<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it6b2upls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="it6b2upls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:baby-female-0203m-negative" {...props}></Icon>
