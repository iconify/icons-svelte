<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/e/eamuywvkw.css';
import '../../css/s/swgf26b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><rect vector-effect="non-scaling-stroke" class="eamuywvkw"/><path vector-effect="non-scaling-stroke" class="swgf26b7q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:copy-small" {...props}></Icon>
