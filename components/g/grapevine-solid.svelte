<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-9ts-tho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-9ts-tho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:grapevine-solid" {...props}></Icon>
