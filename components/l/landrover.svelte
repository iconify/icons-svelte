<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l75yblbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l75yblbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:landrover" {...props}></Icon>
