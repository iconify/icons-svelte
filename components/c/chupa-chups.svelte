<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_spz8nzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_spz8nzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:chupa-chups" {...props}></Icon>
