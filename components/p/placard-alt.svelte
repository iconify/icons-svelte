<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg7b_o56d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sg7b_o56d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:placard-alt" {...props}></Icon>
