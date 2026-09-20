<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6evof38d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w6evof38d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:hot-air-balloon-solid" {...props}></Icon>
