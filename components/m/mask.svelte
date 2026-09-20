<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owjpa7hfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="owjpa7hfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mask" {...props}></Icon>
