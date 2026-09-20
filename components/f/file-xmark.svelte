<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0zmwl6su.css';
import '../../css/d/d_zjijokg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x0zmwl6su"/><path class="d_zjijokg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:file-xmark" {...props}></Icon>
