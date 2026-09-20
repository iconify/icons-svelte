<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbjqhhusm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hbjqhhusm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:nest-wifi-logo-block" {...props}></Icon>
