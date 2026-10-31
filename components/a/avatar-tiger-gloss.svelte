<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbm-2zbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbm-2zbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-tiger-gloss" {...props}></Icon>
