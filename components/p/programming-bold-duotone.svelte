<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/k/k5s-t1b0l.css';
import '../../css/a/augjxln2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="k5s-t1b0l"/><path class="augjxln2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:programming-bold-duotone" {...props}></Icon>
