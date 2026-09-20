<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upbf9b5kk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upbf9b5kk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:arrows-h" {...props}></Icon>
