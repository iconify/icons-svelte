<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7-i0pbve.css';
import '../../css/e/elle6g26i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7-i0pbve"/><path class="elle6g26i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:flower-alt" {...props}></Icon>
