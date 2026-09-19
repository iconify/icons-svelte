<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-aqdfb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-aqdfb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:emergency" {...props}></Icon>
