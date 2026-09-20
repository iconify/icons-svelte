<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/helu_3bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="helu_3bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:html5-line" {...props}></Icon>
