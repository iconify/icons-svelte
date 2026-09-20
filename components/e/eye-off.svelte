<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddwzdff0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddwzdff0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:eye-off" {...props}></Icon>
