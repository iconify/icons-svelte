<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fntzryfta.css';
import '../../css/i/iw2xs4bqm.css';
import '../../css/g/gzjxlqbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fntzryfta"/><path class="iw2xs4bqm"/><path class="gzjxlqbhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:calendar-sync" {...props}></Icon>
