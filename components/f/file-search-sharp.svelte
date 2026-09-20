<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvz-i3byl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvz-i3byl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-search-sharp" {...props}></Icon>
