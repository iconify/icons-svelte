<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unfk_pn7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="unfk_pn7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paperclip4-filled" {...props}></Icon>
