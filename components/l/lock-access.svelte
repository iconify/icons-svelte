<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdaijo30p.css';
import '../../css/j/jevxj9zcd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdaijo30p"/><path class="jevxj9zcd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:lock-access" {...props}></Icon>
