<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojbic-t7m.css';
import '../../css/p/p5vtv8brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojbic-t7m"/><path class="p5vtv8brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:payment-link-light" {...props}></Icon>
