<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0si7bc9c.css';
import '../../css/c/c7ja4vb8i.css';
import '../../css/k/knqltxb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="m0si7bc9c"/><rect class="c7ja4vb8i"/><path class="knqltxb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-vertical-justify-end-filled" {...props}></Icon>
