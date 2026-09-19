<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pejt8hb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":288,"height":512};
const content = `<path class="pejt8hb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:neuter" {...props}></Icon>
