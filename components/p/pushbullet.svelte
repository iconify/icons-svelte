<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmi0dlb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmi0dlb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pushbullet" {...props}></Icon>
