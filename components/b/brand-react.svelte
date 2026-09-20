<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/a1m6vvblk.css';
import '../../css/i/i4mytz8lr.css';
import '../../css/w/wqzdzgbxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a1m6vvblk"/><path class="i4mytz8lr"/><path class="wqzdzgbxx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-react" {...props}></Icon>
