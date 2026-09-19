<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka6cs0bzz.css';
import '../../css/r/rek-56b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka6cs0bzz"/><path class="rek-56b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-stand-filled" {...props}></Icon>
