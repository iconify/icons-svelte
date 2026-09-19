<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gryfkac7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gryfkac7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:radon" {...props}></Icon>
