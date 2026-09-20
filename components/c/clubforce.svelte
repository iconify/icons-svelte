<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9w5rnv8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v9w5rnv8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:clubforce" {...props}></Icon>
