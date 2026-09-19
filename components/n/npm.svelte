<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzb42w0ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hzb42w0ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:npm" {...props}></Icon>
