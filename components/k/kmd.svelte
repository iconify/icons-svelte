<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmjd7wbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":96,"height":96};
const content = `<path clip-rule="evenodd" class="xmjd7wbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:kmd" {...props}></Icon>
