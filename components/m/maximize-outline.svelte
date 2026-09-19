<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doex5ofaj.css';
import '../../css/u/u9i5pqlkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doex5ofaj"/><path class="u9i5pqlkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:maximize-outline" {...props}></Icon>
