<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ripqrslqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ripqrslqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:playpause-fill" {...props}></Icon>
