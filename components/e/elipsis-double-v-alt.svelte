<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8nu23brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8nu23brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:elipsis-double-v-alt" {...props}></Icon>
