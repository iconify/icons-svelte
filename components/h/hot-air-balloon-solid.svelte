<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufe5gzu4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufe5gzu4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hot-air-balloon-solid" {...props}></Icon>
