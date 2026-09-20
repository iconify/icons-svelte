<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md3_2hdpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md3_2hdpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:inbox-remix" {...props}></Icon>
