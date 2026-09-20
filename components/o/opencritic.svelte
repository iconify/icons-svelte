<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s665nnb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s665nnb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:opencritic" {...props}></Icon>
