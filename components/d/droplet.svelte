<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3_yj1ede.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a3_yj1ede"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:droplet" {...props}></Icon>
