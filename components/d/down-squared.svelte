<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tny7lbc-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tny7lbc-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:down-squared" {...props}></Icon>
