<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytg75cb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytg75cb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nbc" {...props}></Icon>
