<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yuk3ct2rx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuk3ct2rx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:known" {...props}></Icon>
