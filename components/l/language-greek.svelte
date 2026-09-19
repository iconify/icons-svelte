<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsb_qgbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bsb_qgbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:language-greek" {...props}></Icon>
