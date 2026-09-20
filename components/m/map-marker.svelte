<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyu6w7b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyu6w7b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:map-marker" {...props}></Icon>
