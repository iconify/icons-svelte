<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlh1tr96n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlh1tr96n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-search-solid" {...props}></Icon>
