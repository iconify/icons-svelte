<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqc-ryket.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqc-ryket"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-10-filled" {...props}></Icon>
