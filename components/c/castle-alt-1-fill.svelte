<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuur59v_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zuur59v_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:castle-alt-1-fill" {...props}></Icon>
