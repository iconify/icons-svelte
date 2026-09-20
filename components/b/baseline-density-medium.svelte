<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5hd6kogk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j5hd6kogk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:baseline-density-medium" {...props}></Icon>
