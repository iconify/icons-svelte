<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyyfkubug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyyfkubug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-heart-solid" {...props}></Icon>
