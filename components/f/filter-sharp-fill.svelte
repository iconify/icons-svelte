<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljndgibjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljndgibjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:filter-sharp-fill" {...props}></Icon>
