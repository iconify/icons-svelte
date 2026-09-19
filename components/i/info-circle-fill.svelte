<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkt0su85n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="gkt0su85n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:info-circle-fill" {...props}></Icon>
