<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbsg529cw.css';
import '../../css/s/sto-m6bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jbsg529cw"/><path class="sto-m6bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:month" {...props}></Icon>
