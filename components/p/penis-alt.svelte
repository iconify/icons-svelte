<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be7cf6b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="be7cf6b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:penis-alt" {...props}></Icon>
