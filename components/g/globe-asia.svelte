<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sukwxlkix.css';
import '../../css/y/y5p1me9xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sukwxlkix"/><path class="y5p1me9xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-asia" {...props}></Icon>
