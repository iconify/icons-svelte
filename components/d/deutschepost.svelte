<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va4l82bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va4l82bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:deutschepost" {...props}></Icon>
