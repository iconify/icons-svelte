<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvf-84bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nvf-84bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:face-very-happy-stroke-12" {...props}></Icon>
