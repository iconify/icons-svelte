<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_pf7lbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_pf7lbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:pin" {...props}></Icon>
