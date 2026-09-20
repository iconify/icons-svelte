<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh03m-bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hh03m-bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:messages-people-user-bubble-circle" {...props}></Icon>
