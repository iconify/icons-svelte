<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8ejirjck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j8ejirjck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:baby-0203m2x-outline" {...props}></Icon>
