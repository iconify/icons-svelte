<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxbl4ccqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxbl4ccqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:qr-code-01" {...props}></Icon>
