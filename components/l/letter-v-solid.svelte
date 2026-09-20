<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p51e5geti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p51e5geti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-v-solid" {...props}></Icon>
