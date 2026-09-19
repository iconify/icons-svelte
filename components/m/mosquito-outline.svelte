<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_2wtsbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f_2wtsbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mosquito-outline" {...props}></Icon>
