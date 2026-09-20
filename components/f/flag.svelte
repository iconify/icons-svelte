<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzmqz21qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dzmqz21qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:flag" {...props}></Icon>
