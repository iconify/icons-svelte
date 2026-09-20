<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mr-knn1jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mr-knn1jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ai-science-robot-solid" {...props}></Icon>
