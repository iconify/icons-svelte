<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9mo31emm.css';
import '../../css/r/r2k-5lb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9mo31emm"/><path class="r2k-5lb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-up-right-circle-filled" {...props}></Icon>
