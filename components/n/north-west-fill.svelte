<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_shrwb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i_shrwb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-west-fill" {...props}></Icon>
