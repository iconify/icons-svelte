<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wntamsb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wntamsb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rocket-fill" {...props}></Icon>
