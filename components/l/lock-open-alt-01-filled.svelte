<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_0hn4skk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_0hn4skk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lock-open-alt-01-filled" {...props}></Icon>
