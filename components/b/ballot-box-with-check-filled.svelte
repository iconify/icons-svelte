<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdba18qql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kdba18qql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ballot-box-with-check-filled" {...props}></Icon>
