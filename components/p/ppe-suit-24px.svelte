<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbrug46qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hbrug46qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-suit-24px" {...props}></Icon>
