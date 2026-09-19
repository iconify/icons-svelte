<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffkma_bxg.css';
import '../../css/o/ob3ntmvsq.css';
import '../../css/h/hntz4fq6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffkma_bxg"/><path class="ob3ntmvsq"/><circle class="hntz4fq6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-rss" {...props}></Icon>
