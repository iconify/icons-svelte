<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpq-ag9ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpq-ag9ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-question-outline" {...props}></Icon>
