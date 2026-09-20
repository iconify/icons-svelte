<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzy__5huq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzy__5huq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:htm" {...props}></Icon>
