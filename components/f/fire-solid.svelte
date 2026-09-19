<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g41g3cfca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g41g3cfca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:fire-solid" {...props}></Icon>
