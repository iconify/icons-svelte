<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z390905ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z390905ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:roadmap-filled" {...props}></Icon>
