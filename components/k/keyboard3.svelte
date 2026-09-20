<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgajv3ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qgajv3ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:keyboard3" {...props}></Icon>
