<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te9dwhb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te9dwhb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:mini-player" {...props}></Icon>
