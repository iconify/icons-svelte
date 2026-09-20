<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6nwf-u2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6nwf-u2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:left-up-line" {...props}></Icon>
