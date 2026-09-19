<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3znfvbta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3znfvbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cloudy-night-sharp" {...props}></Icon>
