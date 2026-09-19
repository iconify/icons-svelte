<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9n2ybc0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9n2ybc0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:caret-right-fill" {...props}></Icon>
