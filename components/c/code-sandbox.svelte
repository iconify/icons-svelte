<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np06j9bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="np06j9bzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:code-sandbox" {...props}></Icon>
