<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dm03gzbnp.css';
import '../../css/j/jcknlfbhs.css';
import '../../css/j/jn4idmyju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="jcknlfbhs"/><path class="jn4idmyju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bones-bold-duotone" {...props}></Icon>
