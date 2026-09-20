<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf3y1xrnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf3y1xrnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:list" {...props}></Icon>
