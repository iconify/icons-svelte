<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlr1md4hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlr1md4hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:list-ui-alt" {...props}></Icon>
