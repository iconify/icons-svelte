<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfahdz_nv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tfahdz_nv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adobe-audition" {...props}></Icon>
