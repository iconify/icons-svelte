<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwwnof78l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bwwnof78l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:emc" {...props}></Icon>
