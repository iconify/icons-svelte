<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hztsqwbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hztsqwbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:partner-verified" {...props}></Icon>
