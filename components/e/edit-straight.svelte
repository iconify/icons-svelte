<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjhaaozbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjhaaozbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:edit-straight" {...props}></Icon>
