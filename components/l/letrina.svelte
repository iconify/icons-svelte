<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3yg1cuow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="x3yg1cuow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:letrina" {...props}></Icon>
