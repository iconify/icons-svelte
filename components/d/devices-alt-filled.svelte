<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zho0a0box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zho0a0box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:devices-alt-filled" {...props}></Icon>
