<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qmljnbb4u.css';
import '../../css/l/l6inxqm2l.css';
import '../../css/c/cbanfebus.css';
import '../../css/i/iubkpvb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qmljnbb4u"/><ellipse class="l6inxqm2l"/><path class="cbanfebus"/><path class="iubkpvb5h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:database-duotone" {...props}></Icon>
