<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuulglbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuulglbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:glasses2-filled" {...props}></Icon>
