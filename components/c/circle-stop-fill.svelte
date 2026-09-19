<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kma08ubea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kma08ubea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-stop-fill" {...props}></Icon>
