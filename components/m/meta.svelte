<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3a4znb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3a4znb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:meta" {...props}></Icon>
