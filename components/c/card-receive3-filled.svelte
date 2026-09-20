<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0g1x7baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0g1x7baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:card-receive3-filled" {...props}></Icon>
