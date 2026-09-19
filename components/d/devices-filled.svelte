<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovbmmccao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ovbmmccao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:devices-filled" {...props}></Icon>
