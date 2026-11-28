<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/tc07prbkf.css';
import '../../css/e/ejnqsif1c.css';
import '../../css/y/ylnbz1h1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tc07prbkf"/><path class="ejnqsif1c"/><path class="ylnbz1h1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:clock-arrow-left" {...props}></Icon>
