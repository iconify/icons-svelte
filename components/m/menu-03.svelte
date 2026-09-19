<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxuprlavv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxuprlavv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:menu-03" {...props}></Icon>
