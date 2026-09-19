<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8w8wzblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="i8w8wzblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:naira" {...props}></Icon>
