<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myo5-e-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myo5-e-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-draft-24" {...props}></Icon>
