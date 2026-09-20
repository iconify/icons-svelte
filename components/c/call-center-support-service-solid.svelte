<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oph0gbbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oph0gbbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:call-center-support-service-solid" {...props}></Icon>
