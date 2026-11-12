<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b103epbdu.css';
import '../../css/w/wre6mlbjq.css';
import '../../css/c/cz6z9n00t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b103epbdu"/><path class="wre6mlbjq"/><path class="cz6z9n00t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:colota-dark" {...props}></Icon>
