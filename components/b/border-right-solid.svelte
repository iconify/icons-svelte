<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k8fkbpohc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="k8fkbpohc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-right-solid" {...props}></Icon>
