<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyovs5gvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hyovs5gvn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-outline-lock" {...props}></Icon>
