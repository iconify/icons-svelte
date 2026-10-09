<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjpr8ebst.css';
import '../../css/f/f_bvfu90l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cjpr8ebst"/><path class="f_bvfu90l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paw-20" {...props}></Icon>
