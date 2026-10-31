<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zixx47u9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zixx47u9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:calendar-edit-fill-round" {...props}></Icon>
