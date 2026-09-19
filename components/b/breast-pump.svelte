<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/f90ii8o0l.css';
import '../../css/b/blcntivod.css';
import '../../css/i/if-72qbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="f90ii8o0l"/><circle class="blcntivod"/><path class="if-72qbbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:breast-pump" {...props}></Icon>
