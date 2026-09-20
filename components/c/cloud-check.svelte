<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/h8ry1tbte.css';
import '../../css/b/b_as47b3j.css';
import '../../css/n/ndki_77_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="h8ry1tbte"/><path class="b_as47b3j"/><path class="ndki_77_h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:cloud-check" {...props}></Icon>
