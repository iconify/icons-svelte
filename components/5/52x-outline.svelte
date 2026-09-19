<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpkjll-eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rpkjll-eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:52x-outline" {...props}></Icon>
