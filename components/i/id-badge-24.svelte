<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu8rqjbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fu8rqjbfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:id-badge-24" {...props}></Icon>
