<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aexgi1bnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":718};
const content = `<path class="aexgi1bnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:ban" {...props}></Icon>
