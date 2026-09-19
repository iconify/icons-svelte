<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oh5ar3jyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oh5ar3jyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:merge-duplicate" {...props}></Icon>
