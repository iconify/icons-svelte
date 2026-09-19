<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpp8mpb8p.css';
import '../../css/r/rg45w14ll.css';
import '../../css/v/vi504dbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpp8mpb8p"/><path class="rg45w14ll"/><path class="vi504dbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fingerprint" {...props}></Icon>
