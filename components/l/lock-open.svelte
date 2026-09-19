<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk81qx38q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gk81qx38q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:lock-open" {...props}></Icon>
