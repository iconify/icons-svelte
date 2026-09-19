<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss8l_1bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss8l_1bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-jakobsbyn" {...props}></Icon>
