<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi_ab-2lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hi_ab-2lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:qualcomm" {...props}></Icon>
