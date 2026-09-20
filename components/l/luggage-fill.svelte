<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjo6nn7py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cjo6nn7py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:luggage-fill" {...props}></Icon>
