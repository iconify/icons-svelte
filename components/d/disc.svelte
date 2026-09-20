<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoqfu3b7n.css';
import '../../css/z/zpm4lyb8b.css';
import '../../css/o/ooafjrbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoqfu3b7n"/><path class="zpm4lyb8b"/><path class="ooafjrbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:disc" {...props}></Icon>
