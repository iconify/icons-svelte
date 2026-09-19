<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqnjgebdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqnjgebdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cloud-drizzle-filled" {...props}></Icon>
