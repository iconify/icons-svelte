<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywm-p_b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ywm-p_b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ram" {...props}></Icon>
