<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0z_ntb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0z_ntb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:align-objects-right" {...props}></Icon>
