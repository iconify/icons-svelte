<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idnpn86mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="idnpn86mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-arrow-down-left-sharp-fill" {...props}></Icon>
