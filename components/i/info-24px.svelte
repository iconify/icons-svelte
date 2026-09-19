<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9xegbb3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9xegbb3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:info-24px" {...props}></Icon>
