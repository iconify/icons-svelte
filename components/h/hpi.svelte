<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0d7_yx6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0d7_yx6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:hpi" {...props}></Icon>
