<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5eu30nwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5eu30nwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:repeat-circle" {...props}></Icon>
