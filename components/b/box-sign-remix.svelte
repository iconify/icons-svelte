<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/korl6q5lr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="korl6q5lr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:box-sign-remix" {...props}></Icon>
