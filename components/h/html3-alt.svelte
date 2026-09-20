<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe-e3cc2p.css';
import '../../css/y/y8v76ebvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fe-e3cc2p"/><path class="y8v76ebvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:html3-alt" {...props}></Icon>
