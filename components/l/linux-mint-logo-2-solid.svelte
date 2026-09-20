<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4q-79nri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r4q-79nri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:linux-mint-logo-2-solid" {...props}></Icon>
