<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtu_soylv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xtu_soylv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bell-remix" {...props}></Icon>
