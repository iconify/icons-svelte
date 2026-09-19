<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5j9tpbei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q5j9tpbei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:layers-two" {...props}></Icon>
