<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr0d2hbau.css';
import '../../css/m/myu93rbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr0d2hbau"/><path class="myu93rbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:prawn-filled" {...props}></Icon>
