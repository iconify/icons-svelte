<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyf2kv-0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gyf2kv-0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paperclip" {...props}></Icon>
