<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igo2_5qvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igo2_5qvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:folder" {...props}></Icon>
