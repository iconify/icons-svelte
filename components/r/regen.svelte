<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-ji5v0kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-ji5v0kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:regen" {...props}></Icon>
