<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uyr_xvayy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyr_xvayy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:hiking-stick" {...props}></Icon>
