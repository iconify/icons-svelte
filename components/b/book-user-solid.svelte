<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjaa4rkcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjaa4rkcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:book-user-solid" {...props}></Icon>
