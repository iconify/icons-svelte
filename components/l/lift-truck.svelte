<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jz-mj0_jb.css';
import '../../css/a/ak742-b8l.css';
import '../../css/e/evq4mdbon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jz-mj0_jb"/><path class="ak742-b8l"/><path class="evq4mdbon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:lift-truck" {...props}></Icon>
