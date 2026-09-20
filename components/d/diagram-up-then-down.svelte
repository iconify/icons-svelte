<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmo9ppb1i.css';
import '../../css/j/jlv4cgy0n.css';
import '../../css/b/bpsgf019b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="lmo9ppb1i"><path class="jlv4cgy0n"/><path class="bpsgf019b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate-color:diagram-up-then-down" {...props}></Icon>
