<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3fkllq0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n3fkllq0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:compass" {...props}></Icon>
