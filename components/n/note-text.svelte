<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdxusgbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdxusgbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:note-text" {...props}></Icon>
