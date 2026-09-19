<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um28_2kaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="um28_2kaf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-9-circle-fill" {...props}></Icon>
