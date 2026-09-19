<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tho4hgacv.css';
import '../../css/l/lj8aahbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tho4hgacv"/><path class="lj8aahbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:home-smile" {...props}></Icon>
