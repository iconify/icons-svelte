<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc892x2wy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pc892x2wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cloud-check-sharp-fill" {...props}></Icon>
