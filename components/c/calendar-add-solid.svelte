<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaybjhg_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uaybjhg_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:calendar-add-solid" {...props}></Icon>
