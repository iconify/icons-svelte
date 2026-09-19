<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am_-jxgiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="am_-jxgiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-cyrillic-small" {...props}></Icon>
