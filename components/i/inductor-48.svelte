<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5nl8rbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v5nl8rbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:inductor-48" {...props}></Icon>
