<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcj-5rgqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dcj-5rgqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:medical-bag-remix" {...props}></Icon>
