<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_refubyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_refubyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-up-right-24" {...props}></Icon>
