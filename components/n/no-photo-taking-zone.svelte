<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rlxecy5gb.css';
import '../../css/a/al5367bds.css';
import '../../css/h/hcflj6-un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rlxecy5gb"/><path class="al5367bds"/><path class="hcflj6-un"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:no-photo-taking-zone" {...props}></Icon>
