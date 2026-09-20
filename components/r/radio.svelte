<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnhl-5bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tnhl-5bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:radio" {...props}></Icon>
