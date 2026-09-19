<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkb-i8_jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="fkb-i8_jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:github" {...props}></Icon>
