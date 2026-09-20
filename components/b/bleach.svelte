<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydz5a80uc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydz5a80uc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bleach" {...props}></Icon>
