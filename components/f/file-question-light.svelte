<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykqyfbb6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ykqyfbb6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-question-light" {...props}></Icon>
