<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu-dbm9zt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tu-dbm9zt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:italic-filled" {...props}></Icon>
