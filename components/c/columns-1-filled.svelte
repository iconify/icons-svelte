<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nuxsz0bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nuxsz0bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:columns-1-filled" {...props}></Icon>
