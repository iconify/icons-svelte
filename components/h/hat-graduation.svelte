<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tat1wobpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tat1wobpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:hat-graduation" {...props}></Icon>
