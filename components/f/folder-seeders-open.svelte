<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfig_ccgd.css';
import '../../css/g/gywkiybpr.css';
import '../../css/n/ncqivtbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":3200,"height":3200};
const content = `<path class="gfig_ccgd"/><path class="gywkiybpr"/><path class="ncqivtbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-seeders-open" {...props}></Icon>
