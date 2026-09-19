<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apee3r9_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="apee3r9_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:list" {...props}></Icon>
