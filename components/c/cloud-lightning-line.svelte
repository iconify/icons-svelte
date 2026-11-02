<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwux80bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwux80bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-lightning-line" {...props}></Icon>
