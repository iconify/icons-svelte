<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okktcyhss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okktcyhss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-merge-both" {...props}></Icon>
