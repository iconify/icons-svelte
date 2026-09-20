<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6u3acbyv.css';
import '../../css/d/d3a2v_bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b6u3acbyv"/><path class="d3a2v_bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:password" {...props}></Icon>
