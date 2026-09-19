<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neukm1fuz.css';
import '../../css/k/kr2jicboj.css';
import '../../css/b/bhbvqjyxk.css';
import '../../css/p/pc0px5b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="neukm1fuz"/><rect class="kr2jicboj"/><rect class="bhbvqjyxk"/><path class="pc0px5b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:qr-filled" {...props}></Icon>
