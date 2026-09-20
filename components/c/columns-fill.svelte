<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4-97lbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4-97lbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:columns-fill" {...props}></Icon>
