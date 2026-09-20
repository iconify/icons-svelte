<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar98n3b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ar98n3b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:flag-filled" {...props}></Icon>
