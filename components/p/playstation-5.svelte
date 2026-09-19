<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sknnvw58m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sknnvw58m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:playstation-5" {...props}></Icon>
