<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojkxv-zzs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ojkxv-zzs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:megaphone-stroke-20" {...props}></Icon>
