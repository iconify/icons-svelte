<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0i9-_kaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0i9-_kaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:pause" {...props}></Icon>
