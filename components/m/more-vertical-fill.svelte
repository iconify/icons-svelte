<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1xy6nh9u.css';
import '../../css/t/toljrtdpg.css';
import '../../css/r/rpxe9ibnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="n1xy6nh9u"/><circle class="toljrtdpg"/><circle class="rpxe9ibnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:more-vertical-fill" {...props}></Icon>
