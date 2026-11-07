<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i09z172-a.css';
import '../../css/v/v_3ka80pa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i09z172-a"/><path class="v_3ka80pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:forward-right-bold-duotone" {...props}></Icon>
