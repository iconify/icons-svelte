<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wp4knqb8q.css';
import '../../css/k/khnsq01cy.css';
import '../../css/i/i5xw9gqsb.css';
import '../../css/e/eaj47cc_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k wp4knqb8q"/><path class="khnsq01cy wm-a"/><path class="i5xw9gqsb wm-k"/><path class="eaj47cc_q wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:palm-tree-sketch" {...props}></Icon>
