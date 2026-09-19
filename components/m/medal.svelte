<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf-21-0mo.css';
import '../../css/d/dum7nab_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gf-21-0mo"/><path class="dum7nab_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:medal" {...props}></Icon>
