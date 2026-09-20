<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m069-ebdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m069-ebdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:dots-vertical-circle" {...props}></Icon>
