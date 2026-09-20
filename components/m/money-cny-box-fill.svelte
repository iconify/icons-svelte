<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmyh23gtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmyh23gtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:money-cny-box-fill" {...props}></Icon>
