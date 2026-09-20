<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqgyks5ti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqgyks5ti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:crowdin" {...props}></Icon>
