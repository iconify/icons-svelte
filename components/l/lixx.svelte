<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq97rccgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eq97rccgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lixx" {...props}></Icon>
