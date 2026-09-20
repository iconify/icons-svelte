<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wufabxb2f.css';
import '../../css/h/hafkb4bxt.css';
import '../../css/c/cdjzimb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wufabxb2f"/><path class="hafkb4bxt"/><path class="cdjzimb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-kmeet-dark" {...props}></Icon>
