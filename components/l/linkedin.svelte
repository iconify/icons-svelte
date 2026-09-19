<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i48rb5bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i48rb5bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:linkedin" {...props}></Icon>
