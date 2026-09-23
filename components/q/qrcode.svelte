<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/j/jfr6wqbhu.css';
import '../../css/l/l78icwe5e.css';
import '../../css/y/yny8akbhl.css';
import '../../css/v/vc38b5b-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><rect class="jfr6wqbhu"/><rect class="l78icwe5e"/><rect class="yny8akbhl"/><path class="vc38b5b-m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:qrcode" {...props}></Icon>
