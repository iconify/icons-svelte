<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljvs4moct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="ljvs4moct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:night-alt-rain" {...props}></Icon>
