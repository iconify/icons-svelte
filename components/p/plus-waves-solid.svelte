<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkdgngpbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkdgngpbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:plus-waves-solid" {...props}></Icon>
