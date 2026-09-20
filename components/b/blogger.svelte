<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_br5ke-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_br5ke-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:blogger" {...props}></Icon>
