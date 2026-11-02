<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tj6kq6b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tj6kq6b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:laptop-2-fill" {...props}></Icon>
