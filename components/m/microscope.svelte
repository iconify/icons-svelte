<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkooz0zfl.css';
import '../../css/z/za8l1lbvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkooz0zfl"/><path class="za8l1lbvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microscope" {...props}></Icon>
