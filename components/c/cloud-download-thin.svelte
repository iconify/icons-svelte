<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/w/wuu1i6jkg.css';
import '../../css/j/ji85o5n5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="wuu1i6jkg"/><path class="ji85o5n5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-download-thin" {...props}></Icon>
