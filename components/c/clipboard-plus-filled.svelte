<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcvhhab3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jcvhhab3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-plus-filled" {...props}></Icon>
