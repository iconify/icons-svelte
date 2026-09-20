<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enco1glmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enco1glmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:creativecommons" {...props}></Icon>
