<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr_r5vbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="fr_r5vbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:crop-solid" {...props}></Icon>
