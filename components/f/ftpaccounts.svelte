<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh9bsgbhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="bh9bsgbhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ftpaccounts" {...props}></Icon>
