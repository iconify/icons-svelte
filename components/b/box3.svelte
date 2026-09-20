<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmis2f9is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmis2f9is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:box3" {...props}></Icon>
