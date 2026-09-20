<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjg4b0fxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tjg4b0fxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:import-fill" {...props}></Icon>
