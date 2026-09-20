<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vghf96kzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vghf96kzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bolt" {...props}></Icon>
