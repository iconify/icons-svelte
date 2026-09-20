<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaizi4b6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aaizi4b6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:guitar-machine-head-24" {...props}></Icon>
