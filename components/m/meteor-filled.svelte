<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnf8t8yjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnf8t8yjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:meteor-filled" {...props}></Icon>
