<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlxcj749n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlxcj749n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-vertical-justify-end" {...props}></Icon>
