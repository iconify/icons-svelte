<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/too40e6yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="too40e6yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:clock-seven" {...props}></Icon>
