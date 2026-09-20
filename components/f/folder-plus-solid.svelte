<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nam14s5tq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nam14s5tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:folder-plus-solid" {...props}></Icon>
