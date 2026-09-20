<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olhfxn-bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olhfxn-bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pass-valid-fill" {...props}></Icon>
