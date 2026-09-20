<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li9_19ptk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li9_19ptk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:adguard" {...props}></Icon>
