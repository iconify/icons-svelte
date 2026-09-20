<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrf7qsi7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrf7qsi7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:line-light" {...props}></Icon>
