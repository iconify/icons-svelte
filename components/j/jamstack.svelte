<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhms3xbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhms3xbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:jamstack" {...props}></Icon>
