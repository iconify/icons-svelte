<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja5incaal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ja5incaal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:inbox-fill-12" {...props}></Icon>
