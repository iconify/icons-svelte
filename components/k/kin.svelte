<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg6-2_tbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jg6-2_tbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:kin" {...props}></Icon>
