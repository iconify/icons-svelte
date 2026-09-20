<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yozvh-bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yozvh-bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hello" {...props}></Icon>
