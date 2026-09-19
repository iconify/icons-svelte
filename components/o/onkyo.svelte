<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak4qt2bvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak4qt2bvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:onkyo" {...props}></Icon>
