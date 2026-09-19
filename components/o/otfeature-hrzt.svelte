<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v71nd2bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="v71nd2bub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-hrzt" {...props}></Icon>
