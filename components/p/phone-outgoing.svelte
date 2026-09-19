<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrgw8tmqm.css';
import '../../css/u/uulyedb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrgw8tmqm"/><path class="uulyedb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:phone-outgoing" {...props}></Icon>
