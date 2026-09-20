<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcxe_dbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fcxe_dbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:protonvpn" {...props}></Icon>
