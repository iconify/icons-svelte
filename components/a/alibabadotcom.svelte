<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg1qlmvrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xg1qlmvrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:alibabadotcom" {...props}></Icon>
