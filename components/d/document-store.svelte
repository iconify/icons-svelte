<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2q-q03ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2q-q03ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document-store" {...props}></Icon>
