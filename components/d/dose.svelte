<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7ejribor.css';
import '../../css/u/urh8tubap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r7ejribor"/><path class="urh8tubap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dose" {...props}></Icon>
