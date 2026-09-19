<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugm-vulhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ugm-vulhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:awards" {...props}></Icon>
