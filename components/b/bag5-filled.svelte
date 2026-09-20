<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3xlvfk9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3xlvfk9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag5-filled" {...props}></Icon>
