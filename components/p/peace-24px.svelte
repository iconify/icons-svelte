<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9m7r_x7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9m7r_x7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:peace-24px" {...props}></Icon>
