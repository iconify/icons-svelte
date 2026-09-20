<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frce2ob2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frce2ob2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:exclamation-24" {...props}></Icon>
