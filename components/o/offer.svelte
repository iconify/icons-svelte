<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afyhz4brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afyhz4brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:offer" {...props}></Icon>
