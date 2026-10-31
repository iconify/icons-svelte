<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iier55b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iier55b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:archive-restore-gloss" {...props}></Icon>
