<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2uim_bve.css';
import '../../css/t/t4fyarb9e.css';
import '../../css/r/ravzi7blj.css';
import '../../css/b/b9_uigb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="o2uim_bve"/><circle class="t4fyarb9e"/><circle class="ravzi7blj"/><path class="b9_uigb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:circle-more" {...props}></Icon>
