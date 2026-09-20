<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwqa2rb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwqa2rb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:passport-line" {...props}></Icon>
