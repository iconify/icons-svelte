<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7jc9sb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h7jc9sb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:hardware-mobile" {...props}></Icon>
