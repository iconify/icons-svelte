<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxeuqzmsn.css';
import '../../css/z/z1--w73xm.css';
import '../../css/q/q3c4j-bql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pxeuqzmsn"/><path class="z1--w73xm"/><path class="q3c4j-bql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-clipboard" {...props}></Icon>
