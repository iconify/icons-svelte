<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8fl3zb2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8fl3zb2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:electron" {...props}></Icon>
