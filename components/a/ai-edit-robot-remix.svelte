<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izue1acve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="izue1acve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ai-edit-robot-remix" {...props}></Icon>
