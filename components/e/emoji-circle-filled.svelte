<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j58-_kbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j58-_kbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:emoji-circle-filled" {...props}></Icon>
