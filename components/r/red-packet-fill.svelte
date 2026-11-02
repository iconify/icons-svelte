<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjat3tp7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjat3tp7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:red-packet-fill" {...props}></Icon>
