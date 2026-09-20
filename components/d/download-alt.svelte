<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4uh-95df.css';
import '../../css/b/bh93e5uni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4uh-95df"/><path class="bh93e5uni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:download-alt" {...props}></Icon>
