<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze_7y96ni.css';
import '../../css/a/az8mb25cu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ze_7y96ni"/><path class="az8mb25cu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:dashboard-light" {...props}></Icon>
