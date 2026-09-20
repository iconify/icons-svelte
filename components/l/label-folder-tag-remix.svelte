<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpkwi3bmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tpkwi3bmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:label-folder-tag-remix" {...props}></Icon>
