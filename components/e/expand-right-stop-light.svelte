<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xosd-cfuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xosd-cfuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:expand-right-stop-light" {...props}></Icon>
