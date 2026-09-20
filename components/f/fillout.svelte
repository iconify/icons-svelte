<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq7cim73m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq7cim73m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:fillout" {...props}></Icon>
