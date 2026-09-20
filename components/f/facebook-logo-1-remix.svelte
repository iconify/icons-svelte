<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dotcomb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dotcomb2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:facebook-logo-1-remix" {...props}></Icon>
