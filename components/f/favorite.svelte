<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr7-_pcoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hr7-_pcoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:favorite" {...props}></Icon>
