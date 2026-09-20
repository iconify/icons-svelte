<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6wkj5prr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6wkj5prr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-square-up-filled" {...props}></Icon>
