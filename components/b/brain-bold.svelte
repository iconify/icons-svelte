<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9im6cc-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d9im6cc-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:brain-bold" {...props}></Icon>
