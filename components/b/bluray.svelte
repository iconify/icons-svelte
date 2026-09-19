<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od1rprkuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od1rprkuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bluray" {...props}></Icon>
