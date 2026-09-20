<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abl8a-bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abl8a-bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-plus-sharp" {...props}></Icon>
