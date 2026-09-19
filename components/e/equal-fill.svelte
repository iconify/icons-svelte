<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrd764yhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wrd764yhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:equal-fill" {...props}></Icon>
