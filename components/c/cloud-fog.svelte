<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/two12q6ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="two12q6ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cloud-fog" {...props}></Icon>
