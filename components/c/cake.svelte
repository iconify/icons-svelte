<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he0c_3b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="he0c_3b2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:cake" {...props}></Icon>
