<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycfta7yog.css';
import '../../css/l/lwrzs1b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycfta7yog"/><path class="lwrzs1b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-oceania" {...props}></Icon>
