<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuw5yubgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuw5yubgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:brain-cog-sharp" {...props}></Icon>
