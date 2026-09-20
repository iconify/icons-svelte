<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u148y6bbs.css';
import '../../css/i/id-v8e4aj.css';
import '../../css/h/h1jg740us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="u148y6bbs"><path class="id-v8e4aj"/><path class="h1jg740us"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:alarm-clock" {...props}></Icon>
