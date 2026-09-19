<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw7c98bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw7c98bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pi" {...props}></Icon>
