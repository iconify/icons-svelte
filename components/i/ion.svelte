<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm3f23fqe.css';
import '../../css/q/qwo6utarj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm3f23fqe"/><path class="qwo6utarj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ion" {...props}></Icon>
