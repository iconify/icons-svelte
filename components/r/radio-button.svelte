<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzyl5_u7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hzyl5_u7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:radio-button" {...props}></Icon>
