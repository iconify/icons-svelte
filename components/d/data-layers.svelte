<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6mx-ub2l.css';
import '../../css/i/iru6fdc4v.css';
import '../../css/m/mq3t55bue.css';
import '../../css/m/m4wse617w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6mx-ub2l"/><path class="iru6fdc4v"/><path class="mq3t55bue"/><path class="m4wse617w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:data-layers" {...props}></Icon>
