<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/to1cgjbzi.css';
import '../../css/p/phhpl4biy.css';
import '../../css/y/y60xx1bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="to1cgjbzi"/><path class="phhpl4biy"/><path class="y60xx1bkg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chemistry-02" {...props}></Icon>
