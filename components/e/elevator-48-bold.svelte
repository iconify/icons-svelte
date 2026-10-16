<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0dbqj1gj.css';
import '../../css/i/io85o8bhu.css';
import '../../css/n/ngq3jibfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b0dbqj1gj"/><path class="io85o8bhu"/><path class="ngq3jibfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:elevator-48-bold" {...props}></Icon>
