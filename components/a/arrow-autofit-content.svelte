<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x99nn_-9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x99nn_-9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-autofit-content" {...props}></Icon>
