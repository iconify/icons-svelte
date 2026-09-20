<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq6iefbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq6iefbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:flag2-filled" {...props}></Icon>
