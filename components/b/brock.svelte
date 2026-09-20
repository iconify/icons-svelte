<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr205bcmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hr205bcmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:brock" {...props}></Icon>
