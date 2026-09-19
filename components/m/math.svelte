<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grs0l_bbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grs0l_bbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:math" {...props}></Icon>
