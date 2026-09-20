<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyh081gqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyh081gqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:directions-2-fill" {...props}></Icon>
