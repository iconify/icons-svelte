<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwhb9892x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwhb9892x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-crosshair" {...props}></Icon>
