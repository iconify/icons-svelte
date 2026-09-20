<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h54lv3j8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h54lv3j8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-empty-remove" {...props}></Icon>
