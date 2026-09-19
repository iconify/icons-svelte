<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/affnekbuy.css';
import '../../css/w/wd3gak68y.css';
import '../../css/x/xu1bf4b6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="affnekbuy"/><path class="wd3gak68y"/><path class="xu1bf4b6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:eye-closed-outline" {...props}></Icon>
