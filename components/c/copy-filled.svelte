<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eizigmdoq.css';
import '../../css/c/czpw7jf4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="eizigmdoq"/><path class="czpw7jf4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:copy-filled" {...props}></Icon>
