<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elagj-87b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="elagj-87b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:caret-left-filled" {...props}></Icon>
