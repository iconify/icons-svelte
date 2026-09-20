<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5ua0i-bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5ua0i-bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:film-edit-outline" {...props}></Icon>
