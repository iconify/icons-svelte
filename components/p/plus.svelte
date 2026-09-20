<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug6dl0bdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug6dl0bdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:plus" {...props}></Icon>
