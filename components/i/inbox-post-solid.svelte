<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au6banbgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="au6banbgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:inbox-post-solid" {...props}></Icon>
