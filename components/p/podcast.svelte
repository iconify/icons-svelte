<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lex4kb0jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="lex4kb0jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:podcast" {...props}></Icon>
