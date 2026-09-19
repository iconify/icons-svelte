<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_mcmiblg.css';
import '../../css/y/y73gmufio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_mcmiblg"/><path class="y73gmufio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:application-instance-outlined" {...props}></Icon>
