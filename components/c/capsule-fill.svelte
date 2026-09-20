<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqrfsh1mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqrfsh1mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:capsule-fill" {...props}></Icon>
