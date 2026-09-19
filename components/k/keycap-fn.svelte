<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftc2pcbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ftc2pcbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-fn" {...props}></Icon>
