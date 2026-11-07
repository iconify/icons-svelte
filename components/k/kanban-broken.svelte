<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b4f6f8byj.css';
import '../../css/q/qren0kb9n.css';
import '../../css/e/e0z-6ee1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b4f6f8byj"/><path class="qren0kb9n"/><path class="e0z-6ee1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:kanban-broken" {...props}></Icon>
