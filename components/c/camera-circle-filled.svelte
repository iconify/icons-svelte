<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/k5-vjlrin.css';
import '../../css/k/kvn14gsjy.css';
import '../../css/m/my3cj9b3w.css';
import '../../css/c/csed3cbwq.css';
import '../../css/b/bd9gczbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="ft5dv1b6b"><defs><mask id="SVGHHxSAbSC"><path class="k5-vjlrin"/><g clip-rule="evenodd" class="kvn14gsjy"><path class="my3cj9b3w"/><path class="csed3cbwq"/></g></mask></defs><circle mask="url(#SVGHHxSAbSC)" class="bd9gczbnq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:camera-circle-filled" {...props}></Icon>
