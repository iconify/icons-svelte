<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz47_7v9x.css';
import '../../css/n/n9qbr_l5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz47_7v9x"/><path class="n9qbr_l5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:person-cursor-24" {...props}></Icon>
