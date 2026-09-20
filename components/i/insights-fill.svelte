<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw4bdl56u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aw4bdl56u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:insights-fill" {...props}></Icon>
