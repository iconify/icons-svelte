<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsm9vtg9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsm9vtg9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:heart-solid" {...props}></Icon>
