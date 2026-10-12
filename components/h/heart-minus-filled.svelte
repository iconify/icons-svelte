<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikrl6obvt.css';
import '../../css/o/omixov_3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikrl6obvt"/><path class="omixov_3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:heart-minus-filled" {...props}></Icon>
