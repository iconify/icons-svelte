<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjfrobb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjfrobb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoticon-dog" {...props}></Icon>
