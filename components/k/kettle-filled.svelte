<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p93r2t4tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p93r2t4tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:kettle-filled" {...props}></Icon>
