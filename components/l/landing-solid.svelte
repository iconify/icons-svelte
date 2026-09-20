<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly_jofbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="ly_jofbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:landing-solid" {...props}></Icon>
