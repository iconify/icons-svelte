<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_89dgpnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="w_89dgpnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-circle-up-right-f" {...props}></Icon>
