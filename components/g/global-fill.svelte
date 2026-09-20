<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v33-9ibjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v33-9ibjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:global-fill" {...props}></Icon>
