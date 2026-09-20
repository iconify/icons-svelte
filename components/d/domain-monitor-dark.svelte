<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zejmubckr.css';
import '../../css/d/dy9twxbqe.css';
import '../../css/d/d2oowm1mw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zejmubckr"/><path class="dy9twxbqe"/><path class="d2oowm1mw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:domain-monitor-dark" {...props}></Icon>
