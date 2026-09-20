<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_nts0kjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="v_nts0kjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-right-stipple" {...props}></Icon>
