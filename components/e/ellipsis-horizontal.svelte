<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wswh81j3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wswh81j3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:ellipsis-horizontal" {...props}></Icon>
