<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n07jc6bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n07jc6bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-up-lines" {...props}></Icon>
