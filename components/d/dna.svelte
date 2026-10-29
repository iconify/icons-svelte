<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk_1psu1o.css';
import '../../css/g/gx-lz3vja.css';
import '../../css/d/dj2mub87f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk_1psu1o wm-a"/><path class="gx-lz3vja wm-k"/><path class="dj2mub87f wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:dna" {...props}></Icon>
