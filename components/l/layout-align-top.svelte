<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlrjk96mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlrjk96mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:layout-align-top" {...props}></Icon>
