<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k89onwb0c.css';
import '../../css/z/zlth73b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k89onwb0c"/><path clip-rule="evenodd" class="zlth73b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medical-kit-bold" {...props}></Icon>
