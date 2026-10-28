<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nn6g8ebuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nn6g8ebuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nibe-alt2" {...props}></Icon>
