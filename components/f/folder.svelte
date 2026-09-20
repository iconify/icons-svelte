<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-7xz0k4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-7xz0k4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder" {...props}></Icon>
