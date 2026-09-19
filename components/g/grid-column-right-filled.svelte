<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpbvj0b9n.css';
import '../../css/n/neukm1fuz.css';
import '../../css/k/kr2jicboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="xpbvj0b9n"/><rect class="neukm1fuz"/><rect class="kr2jicboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:grid-column-right-filled" {...props}></Icon>
