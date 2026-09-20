<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o33x41uvf.css';
import '../../css/k/ka78z0bui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o33x41uvf"/><path class="ka78z0bui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:heart-duotone" {...props}></Icon>
