<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifuw65ceo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ifuw65ceo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nuls" {...props}></Icon>
