<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr4mq5bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr4mq5bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-fill" {...props}></Icon>
