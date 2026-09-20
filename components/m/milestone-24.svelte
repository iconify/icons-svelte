<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw-wxwb6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw-wxwb6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:milestone-24" {...props}></Icon>
