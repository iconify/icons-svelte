<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv7p1jn3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lv7p1jn3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:archive" {...props}></Icon>
