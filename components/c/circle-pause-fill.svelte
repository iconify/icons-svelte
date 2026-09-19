<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa-qvu2lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sa-qvu2lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-pause-fill" {...props}></Icon>
