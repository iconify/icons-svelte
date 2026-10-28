<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjpr_6-3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjpr_6-3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-up-a-z" {...props}></Icon>
