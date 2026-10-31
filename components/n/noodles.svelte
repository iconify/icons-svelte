<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1guqcscz.css';
import '../../css/o/ontwibcre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o1guqcscz"/><path class="ontwibcre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:noodles" {...props}></Icon>
