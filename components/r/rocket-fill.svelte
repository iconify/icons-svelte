<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5hcwdbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="r5hcwdbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rocket-fill" {...props}></Icon>
