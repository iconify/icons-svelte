<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozr_udb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ozr_udb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:christmas-hat-fill" {...props}></Icon>
