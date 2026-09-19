<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rou2qjbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rou2qjbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-stack-overflow" {...props}></Icon>
