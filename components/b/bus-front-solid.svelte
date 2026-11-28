<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqt0qnb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqt0qnb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bus-front-solid" {...props}></Icon>
