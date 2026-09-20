<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvnkohbhv.css';
import '../../css/t/txu2pvbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lvnkohbhv"/><path class="txu2pvbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:porkbun" {...props}></Icon>
