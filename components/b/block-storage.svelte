<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n10napp6q.css';
import '../../css/z/zi-9qcbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n10napp6q"/><path class="zi-9qcbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:block-storage" {...props}></Icon>
