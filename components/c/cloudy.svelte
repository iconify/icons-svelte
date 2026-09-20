<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmcl-smta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmcl-smta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:cloudy" {...props}></Icon>
