<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1neirbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1neirbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:diamond-solid" {...props}></Icon>
