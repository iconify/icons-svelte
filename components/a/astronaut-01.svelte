<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/n/n72rw4b2e.css';
import '../../css/p/p70horb1t.css';
import '../../css/p/pojivdb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="n72rw4b2e"/><path class="p70horb1t"/><path class="pojivdb0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:astronaut-01" {...props}></Icon>
