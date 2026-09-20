<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaq71vsnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaq71vsnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-line" {...props}></Icon>
