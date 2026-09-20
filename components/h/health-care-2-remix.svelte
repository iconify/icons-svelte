<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwnyw_b-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nwnyw_b-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:health-care-2-remix" {...props}></Icon>
