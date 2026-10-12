<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5tb85boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5tb85boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:arrow-right-from-line" {...props}></Icon>
