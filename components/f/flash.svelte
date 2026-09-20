<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxc3adbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxc3adbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:flash" {...props}></Icon>
