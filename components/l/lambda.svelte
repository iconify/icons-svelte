<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bifbx49_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bifbx49_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lambda" {...props}></Icon>
