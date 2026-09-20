<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdj-7nb0w.css';
import '../../css/t/tbhf0lycc.css';
import '../../css/w/wei4ynt1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":160,"height":68.7,"top":45.65};
const content = `<path class="gdj-7nb0w"/><path class="tbhf0lycc"/><path class="wei4ynt1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bolt-light" {...props}></Icon>
