<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq-xpubti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":799,"height":658};
const content = `<path class="bq-xpubti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:exchange" {...props}></Icon>
