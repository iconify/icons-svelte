<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1ou3r4ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1ou3r4ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:openai" {...props}></Icon>
