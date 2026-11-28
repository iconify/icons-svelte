<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aifiwxboo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aifiwxboo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mic-solid" {...props}></Icon>
