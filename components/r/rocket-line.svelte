<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd-l39ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd-l39ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:rocket-line" {...props}></Icon>
