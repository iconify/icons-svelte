<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc6iltb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc6iltb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:blocked-24" {...props}></Icon>
