<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipefi82fx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipefi82fx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-risbyn" {...props}></Icon>
