<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/s/s1l5a3baz.css';
import '../../css/a/af6vrvbxh.css';
import '../../css/f/f9cq2cc0w.css';
import '../../css/s/skq-4gbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="s1l5a3baz"/><path class="af6vrvbxh"/><path class="f9cq2cc0w"/><path class="skq-4gbyv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:martini" {...props}></Icon>
