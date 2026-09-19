<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk_glsbdf.css';
import '../../css/r/r3m6txini.css';
import '../../css/z/z5lj_d9rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pk_glsbdf"/><path class="r3m6txini"/><path class="z5lj_d9rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:fridge" {...props}></Icon>
