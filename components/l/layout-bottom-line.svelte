<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w367kk4-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w367kk4-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-bottom-line" {...props}></Icon>
