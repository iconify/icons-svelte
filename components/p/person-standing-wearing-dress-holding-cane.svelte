<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_tjqsbzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t_tjqsbzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-standing-wearing-dress-holding-cane" {...props}></Icon>
