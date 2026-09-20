<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo9hubbac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mo9hubbac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:ai-folder-robot-remix" {...props}></Icon>
