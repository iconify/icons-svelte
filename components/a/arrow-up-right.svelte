<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnicq_j2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnicq_j2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:arrow-up-right" {...props}></Icon>
