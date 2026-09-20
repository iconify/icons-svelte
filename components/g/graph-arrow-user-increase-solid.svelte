<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kotf-_org.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="kotf-_org"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:graph-arrow-user-increase-solid" {...props}></Icon>
