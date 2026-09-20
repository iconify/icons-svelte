<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cezb6vb6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cezb6vb6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:beaker-minus-outline" {...props}></Icon>
