<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpdw78y7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="zpdw78y7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:money-box" {...props}></Icon>
