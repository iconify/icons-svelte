<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/escl5q8dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="escl5q8dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:meteor" {...props}></Icon>
