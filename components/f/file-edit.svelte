<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1jr9rmik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z1jr9rmik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-edit" {...props}></Icon>
