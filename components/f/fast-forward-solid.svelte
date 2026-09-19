<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_1mesb2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r_1mesb2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:fast-forward-solid" {...props}></Icon>
