<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tss2_kbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tss2_kbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nextbike" {...props}></Icon>
