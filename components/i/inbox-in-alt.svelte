<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl866acnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wl866acnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:inbox-in-alt" {...props}></Icon>
