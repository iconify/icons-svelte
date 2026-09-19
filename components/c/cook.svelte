<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9r4x3jzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e9r4x3jzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cook" {...props}></Icon>
