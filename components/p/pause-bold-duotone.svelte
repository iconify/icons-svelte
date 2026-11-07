<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj208xbck.css';
import '../../css/g/gz18a5efe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj208xbck"/><path class="gz18a5efe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pause-bold-duotone" {...props}></Icon>
