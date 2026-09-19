<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3tpki16g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3tpki16g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:captions-cc-filled" {...props}></Icon>
