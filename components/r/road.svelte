<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8gp7h6jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8gp7h6jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:road" {...props}></Icon>
