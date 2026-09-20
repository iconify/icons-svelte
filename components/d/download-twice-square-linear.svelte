<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qx4kgzb8b.css';
import '../../css/b/b8qhiqbyw.css';
import '../../css/y/yho9nxbfe.css';
import '../../css/p/pw8f5c0fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qx4kgzb8b"/><path class="b8qhiqbyw"/><path class="yho9nxbfe"/><path class="pw8f5c0fp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:download-twice-square-linear" {...props}></Icon>
