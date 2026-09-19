<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agc6-r88p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agc6-r88p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:dropbox" {...props}></Icon>
