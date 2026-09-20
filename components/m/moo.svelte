<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p78xjcq1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p78xjcq1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:moo" {...props}></Icon>
