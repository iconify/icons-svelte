<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5v7x3bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5v7x3bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:lock-24" {...props}></Icon>
