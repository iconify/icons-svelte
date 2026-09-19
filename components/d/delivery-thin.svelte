<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgzv_db-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgzv_db-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:delivery-thin" {...props}></Icon>
