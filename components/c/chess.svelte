<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs88z6b4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs88z6b4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:chess" {...props}></Icon>
