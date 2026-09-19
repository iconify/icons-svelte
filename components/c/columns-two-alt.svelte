<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhjtetu5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bhjtetu5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:columns-two-alt" {...props}></Icon>
