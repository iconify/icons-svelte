<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsx9eqb7z.css';
import '../../css/t/t0y9dydjl.css';
import '../../css/v/v96txsrdu.css';
import '../../css/d/d7-7yjbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dsx9eqb7z"/><path class="t0y9dydjl"/><path class="v96txsrdu"/><path class="d7-7yjbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-storage-20-bold" {...props}></Icon>
