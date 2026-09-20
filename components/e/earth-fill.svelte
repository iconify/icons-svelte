<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jisuh7bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jisuh7bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:earth-fill" {...props}></Icon>
