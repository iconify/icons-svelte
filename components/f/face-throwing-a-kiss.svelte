<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo6vuyb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fo6vuyb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:face-throwing-a-kiss" {...props}></Icon>
