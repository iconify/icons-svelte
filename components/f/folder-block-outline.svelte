<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w71c_izcc.css';
import '../../css/v/vawhvpbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w71c_izcc"/><path clip-rule="evenodd" class="vawhvpbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:folder-block-outline" {...props}></Icon>
