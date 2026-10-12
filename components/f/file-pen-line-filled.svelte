<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw4mfbbve.css';
import '../../css/i/iz0jpn4au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tw4mfbbve"/><path class="iz0jpn4au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:file-pen-line-filled" {...props}></Icon>
