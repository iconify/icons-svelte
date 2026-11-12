<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfjxzhuch.css';
import '../../css/g/gee3w9bni.css';
import '../../css/b/b7vxt34gn.css';
import '../../css/k/kdivkab0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bfjxzhuch"/><path class="gee3w9bni"/><path class="b7vxt34gn"/><path class="kdivkab0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-mail" {...props}></Icon>
