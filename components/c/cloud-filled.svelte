<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hordw4sql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hordw4sql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cloud-filled" {...props}></Icon>
