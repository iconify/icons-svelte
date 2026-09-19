<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te1hwkbud.css';
import '../../css/b/bkh5a45lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te1hwkbud"/><path class="bkh5a45lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:psychology-filled" {...props}></Icon>
