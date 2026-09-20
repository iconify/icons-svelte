<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvwtqr81i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvwtqr81i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:laptop-windows" {...props}></Icon>
