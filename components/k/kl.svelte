<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppi1g2beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppi1g2beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:kl" {...props}></Icon>
