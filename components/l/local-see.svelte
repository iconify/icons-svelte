<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqntgacbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fqntgacbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:local-see" {...props}></Icon>
