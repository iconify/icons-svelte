<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk0r7efoy.css';
import '../../css/e/e1p3xu3iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk0r7efoy"/><path class="e1p3xu3iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:npm-outline" {...props}></Icon>
