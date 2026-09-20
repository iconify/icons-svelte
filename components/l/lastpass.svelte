<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqkcu_b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqkcu_b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:lastpass" {...props}></Icon>
