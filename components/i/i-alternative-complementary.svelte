<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krumclx4i.css';
import '../../css/n/nvoqp-sdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":64};
const content = `<path class="krumclx4i"/><path class="nvoqp-sdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-alternative-complementary" {...props}></Icon>
