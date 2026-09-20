<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_zr_mbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_zr_mbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:banknote-2-outline" {...props}></Icon>
