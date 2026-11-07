<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj208xbck.css';
import '../../css/t/takxuugoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj208xbck"/><path class="takxuugoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pause-bold" {...props}></Icon>
