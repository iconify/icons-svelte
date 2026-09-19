<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvt4vs8ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvt4vs8ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:espn" {...props}></Icon>
