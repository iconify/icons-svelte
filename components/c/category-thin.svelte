<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/q/qx3xlwd4u.css';
import '../../css/a/a96k7rbus.css';
import '../../css/x/xsz6yoa7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="qx3xlwd4u"/><circle class="a96k7rbus"/><path class="xsz6yoa7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:category-thin" {...props}></Icon>
