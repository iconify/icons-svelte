<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcta5_bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcta5_bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:euro-filled" {...props}></Icon>
