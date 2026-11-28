<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twfwmdqjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="twfwmdqjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cylinder" {...props}></Icon>
