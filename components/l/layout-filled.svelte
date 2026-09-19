<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_9xcw95k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_9xcw95k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:layout-filled" {...props}></Icon>
