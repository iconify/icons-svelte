<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9g4i2m7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9g4i2m7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panel-left" {...props}></Icon>
