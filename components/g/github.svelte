<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un7e-x04j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un7e-x04j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:github" {...props}></Icon>
