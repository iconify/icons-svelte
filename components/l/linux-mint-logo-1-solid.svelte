<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5pzh1ksk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5pzh1ksk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:linux-mint-logo-1-solid" {...props}></Icon>
