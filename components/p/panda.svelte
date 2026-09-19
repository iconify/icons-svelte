<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhb7xqbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="rhb7xqbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:panda" {...props}></Icon>
