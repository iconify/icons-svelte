<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1ndafb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1ndafb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pencil-line" {...props}></Icon>
