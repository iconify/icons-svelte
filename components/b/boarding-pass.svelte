<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhapswbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nhapswbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:boarding-pass" {...props}></Icon>
