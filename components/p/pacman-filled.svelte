<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_h9y-bqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_h9y-bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pacman-filled" {...props}></Icon>
