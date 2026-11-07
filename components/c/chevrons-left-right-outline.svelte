<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsygtybgy.css';
import '../../css/j/jwomz4bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsygtybgy"/><path class="jwomz4bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-left-right-outline" {...props}></Icon>
