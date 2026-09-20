<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfndtr6jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfndtr6jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:northeast-southwest-duotone" {...props}></Icon>
