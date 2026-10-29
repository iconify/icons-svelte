<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fv552nidk.css';
import '../../css/a/a714wabld.css';
import '../../css/y/y-o80nbrs.css';
import '../../css/p/pf9cqzq4q.css';
import '../../css/f/fcqp69bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fv552nidk wm-k"/><path class="a714wabld wm-a"/><path class="wm-shadow y-o80nbrs"/><path class="pf9cqzq4q wm-k"/><path class="fcqp69bgt wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:laptop-engrave" {...props}></Icon>
