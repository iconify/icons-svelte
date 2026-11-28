<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0dys392l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0dys392l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pinterest-solid" {...props}></Icon>
