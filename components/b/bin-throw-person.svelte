<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3l9shbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3l9shbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:bin-throw-person" {...props}></Icon>
