<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_7t4ubcy.css';
import '../../css/d/dbpvorrsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_7t4ubcy"/><path class="dbpvorrsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-merge" {...props}></Icon>
