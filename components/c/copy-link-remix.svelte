<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq9artb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aq9artb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:copy-link-remix" {...props}></Icon>
