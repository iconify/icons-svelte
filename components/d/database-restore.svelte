<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/m/mwz9-fkga.css';
import '../../css/e/e6oe62cde.css';
import '../../css/b/bthouvbra.css';
import '../../css/j/jlxgqlbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><ellipse class="mwz9-fkga"/><path class="e6oe62cde"/><path class="bthouvbra"/><path class="jlxgqlbic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:database-restore" {...props}></Icon>
