<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_fvrflbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="i_fvrflbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ghost" {...props}></Icon>
