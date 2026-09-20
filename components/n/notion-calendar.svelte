<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxq-hubfm.css';
import '../../css/z/zylz4v1cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dxq-hubfm"/><path class="zylz4v1cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notion-calendar" {...props}></Icon>
