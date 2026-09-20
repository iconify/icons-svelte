<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-yi4p56d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o-yi4p56d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:beer-pitch-solid" {...props}></Icon>
