<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fut96rbkh.css';
import '../../css/w/waobp-biz.css';
import '../../css/v/v5ifasbxi.css';
import '../../css/f/fb9fhtmzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fut96rbkh"/><path class="waobp-biz"/><path class="v5ifasbxi"/><path class="fb9fhtmzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-contacts" {...props}></Icon>
