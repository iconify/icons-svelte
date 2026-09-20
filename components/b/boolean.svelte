<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kff4x-c4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kff4x-c4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:boolean" {...props}></Icon>
