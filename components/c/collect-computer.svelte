<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qka82ly9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qka82ly9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:collect-computer" {...props}></Icon>
