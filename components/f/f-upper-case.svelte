<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac_v2wbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":735};
const content = `<path class="ac_v2wbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:f-upper-case" {...props}></Icon>
