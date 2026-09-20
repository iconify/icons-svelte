<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzq3j2bza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="dzq3j2bza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:escalator-up-solid" {...props}></Icon>
