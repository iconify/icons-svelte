<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3uq27-sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3uq27-sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ccc" {...props}></Icon>
