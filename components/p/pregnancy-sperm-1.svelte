<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeaf2n6lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeaf2n6lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pregnancy-sperm-1" {...props}></Icon>
