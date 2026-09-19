<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djv6i7b0m.css';
import '../../css/j/jf_6np9ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="djv6i7b0m"/><path class="jf_6np9ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-hotel" {...props}></Icon>
