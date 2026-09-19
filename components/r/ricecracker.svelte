<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofhjkacrl.css';
import '../../css/g/g53_4wpqu.css';
import '../../css/b/b7ri4q8vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="ofhjkacrl"/><path class="g53_4wpqu"/><path class="b7ri4q8vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:ricecracker" {...props}></Icon>
