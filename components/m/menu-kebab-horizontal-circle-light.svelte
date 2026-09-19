<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/u/uuky_gise.css';
import '../../css/p/p4dhxku3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><circle class="uuky_gise"/><path class="p4dhxku3n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-kebab-horizontal-circle-light" {...props}></Icon>
