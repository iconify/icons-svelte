<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/us0n5v1sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="us0n5v1sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:flag-alt-filled" {...props}></Icon>
