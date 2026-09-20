<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkam1aclb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tkam1aclb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:deepfake-technology-2-remix" {...props}></Icon>
