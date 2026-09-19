<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm-8qacrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm-8qacrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:boot-filled" {...props}></Icon>
