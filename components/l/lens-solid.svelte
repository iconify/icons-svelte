<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmi-y2bsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nmi-y2bsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:lens-solid" {...props}></Icon>
