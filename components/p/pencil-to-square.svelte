<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtem9bcpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="gtem9bcpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:pencil-to-square" {...props}></Icon>
