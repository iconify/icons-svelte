<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwdolb3yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gwdolb3yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:bolt-slash-solid" {...props}></Icon>
