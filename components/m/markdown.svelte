<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiq111b5p.css';
import '../../css/y/ybd9n1b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oiq111b5p"/><path class="ybd9n1b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:markdown" {...props}></Icon>
