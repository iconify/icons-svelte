<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/p/piudvvb6v.css';
import '../../css/r/rcxwt6bbg.css';
import '../../css/a/ajaqpvbas.css';
import '../../css/o/ou0fjm6nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="piudvvb6v wm-shadow"/><path class="rcxwt6bbg wm-shadow"/><path class="ajaqpvbas"/><path class="ou0fjm6nt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:check" {...props}></Icon>
