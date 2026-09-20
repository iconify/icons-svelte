<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-5p42bec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x-5p42bec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ai-generate-portrait-image-spark-remix" {...props}></Icon>
