<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp56z7bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mp56z7bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:cloud-data-transfer-solid" {...props}></Icon>
