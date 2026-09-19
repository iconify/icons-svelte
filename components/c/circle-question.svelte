<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st6lq75ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st6lq75ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:circle-question" {...props}></Icon>
