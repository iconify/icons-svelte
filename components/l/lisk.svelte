<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4ukchbsd.css';
import '../../css/p/pj2uctt-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4ukchbsd"/><path class="pj2uctt-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lisk" {...props}></Icon>
