<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9ulrkxay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9ulrkxay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:cafeteria" {...props}></Icon>
