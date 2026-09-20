<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bze682cdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bze682cdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:greater-than" {...props}></Icon>
