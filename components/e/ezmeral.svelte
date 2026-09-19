<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lityu_b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":24};
const content = `<path class="lityu_b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:ezmeral" {...props}></Icon>
