<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czu4wbtlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czu4wbtlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:360-view" {...props}></Icon>
