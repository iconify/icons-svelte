<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bak9dbcyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":507,"height":512};
const content = `<path class="bak9dbcyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:microsoft-outlook" {...props}></Icon>
