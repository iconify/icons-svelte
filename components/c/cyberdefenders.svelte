<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg8qhc6do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kg8qhc6do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:cyberdefenders" {...props}></Icon>
