<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocku_jbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ocku_jbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:clubs-symbol-solid" {...props}></Icon>
