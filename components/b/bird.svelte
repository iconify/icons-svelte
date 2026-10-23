<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oao_oqtzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oao_oqtzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:bird" {...props}></Icon>
