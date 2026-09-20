<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyl9-3bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyl9-3bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:empty-clipboard-remix" {...props}></Icon>
