<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwsg98rff.css';
import '../../css/g/g9wb33bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwsg98rff"/><path class="g9wb33bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:layers-plus-alt-filled" {...props}></Icon>
