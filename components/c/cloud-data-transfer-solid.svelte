<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1433jbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q1433jbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cloud-data-transfer-solid" {...props}></Icon>
