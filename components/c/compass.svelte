<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/i/i9x5yqbwe.css';
import '../../css/b/bikvxdbad.css';
import '../../css/s/s8uiupbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="i9x5yqbwe"/><path class="bikvxdbad"/><path class="s8uiupbae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:compass" {...props}></Icon>
