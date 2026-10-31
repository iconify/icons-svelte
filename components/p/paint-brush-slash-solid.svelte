<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_dzrn5tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p_dzrn5tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:paint-brush-slash-solid" {...props}></Icon>
