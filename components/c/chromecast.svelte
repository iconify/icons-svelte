<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l34wzp3oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l34wzp3oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:chromecast" {...props}></Icon>
