<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxxoc1biv.css';
import '../../css/i/i2771o-vm.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/o/oqc87sf7z.css';
import '../../css/t/t4swahbuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="wxxoc1biv"/><path class="i2771o-vm"/><g class="jn8qy4bru"><path class="oqc87sf7z"/><path class="t4swahbuy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:mastodon" {...props}></Icon>
