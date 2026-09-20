<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3rztpdiw.css';
import '../../css/l/l86idpbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z3rztpdiw"/><path class="l86idpbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chart-grid" {...props}></Icon>
