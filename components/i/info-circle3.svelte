<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdek--bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdek--bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:info-circle3" {...props}></Icon>
