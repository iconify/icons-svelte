<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi9--gyly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi9--gyly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:radar-solid" {...props}></Icon>
