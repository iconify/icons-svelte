<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kompcmmsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kompcmmsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:block-three" {...props}></Icon>
