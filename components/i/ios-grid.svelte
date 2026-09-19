<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj9htxb2j.css';
import '../../css/q/qjl0smrdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fj9htxb2j"/><path class="qjl0smrdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-grid" {...props}></Icon>
