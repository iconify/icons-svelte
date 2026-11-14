<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mf3vz4bbl.css';
import '../../css/e/e72pf88yi.css';
import '../../css/y/y01ji0mmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="mf3vz4bbl"/><path class="e72pf88yi"/><path class="y01ji0mmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:message-secure-02" {...props}></Icon>
