<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdagnjbde.css';
import '../../css/w/wjgo_ebim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hdagnjbde"/><path class="wjgo_ebim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:cog" {...props}></Icon>
