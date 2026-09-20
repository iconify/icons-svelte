<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d08wqdb5c.css';
import '../../css/s/sc9v9pb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d08wqdb5c"/><path class="sc9v9pb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:image-file-eps-bold" {...props}></Icon>
