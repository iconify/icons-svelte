<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/leac04log.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leac04log"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ellevio" {...props}></Icon>
