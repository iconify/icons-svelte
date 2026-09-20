<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0ltb5bzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q0ltb5bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:google-drive" {...props}></Icon>
