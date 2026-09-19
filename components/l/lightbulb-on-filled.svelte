<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc02dkb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gc02dkb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:lightbulb-on-filled" {...props}></Icon>
