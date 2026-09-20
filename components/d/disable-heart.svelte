<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwfmumbyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gwfmumbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:disable-heart" {...props}></Icon>
