<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb358qb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="sb358qb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:printer-f" {...props}></Icon>
