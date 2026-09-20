<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc_qa9b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oc_qa9b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:insurance-hands-solid" {...props}></Icon>
