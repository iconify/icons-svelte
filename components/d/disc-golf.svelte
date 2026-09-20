<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-xhi6odf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-xhi6odf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:disc-golf" {...props}></Icon>
