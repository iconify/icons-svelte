<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihphb4blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihphb4blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:lazyvim" {...props}></Icon>
