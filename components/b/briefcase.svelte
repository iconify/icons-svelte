<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6qutdb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g6qutdb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:briefcase" {...props}></Icon>
