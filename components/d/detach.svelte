<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6up6k9ch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6up6k9ch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:detach" {...props}></Icon>
