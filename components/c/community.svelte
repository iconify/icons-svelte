<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q033zj_ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q033zj_ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:community" {...props}></Icon>
