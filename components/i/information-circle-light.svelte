<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/u/uuky_gise.css';
import '../../css/p/pftnf9bpg.css';
import '../../css/p/p196trped.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><circle class="uuky_gise"/><path class="pftnf9bpg"/><path class="p196trped"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:information-circle-light" {...props}></Icon>
