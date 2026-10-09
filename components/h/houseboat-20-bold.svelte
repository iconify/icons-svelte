<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fspafybgd.css';
import '../../css/f/fw66xi3qj.css';
import '../../css/a/ayok7_nhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fspafybgd"/><path class="fw66xi3qj"/><path class="ayok7_nhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:houseboat-20-bold" {...props}></Icon>
