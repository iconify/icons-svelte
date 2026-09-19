<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icd85j45o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1536};
const content = `<path class="icd85j45o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:paragraph" {...props}></Icon>
