<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v-kj__bya.css';
import '../../css/w/w1idgzhlw.css';
import '../../css/j/jbukd8bpm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcfvsCdsn"><g class="ft5dv1b6b"><path clip-rule="evenodd" class="v-kj__bya"/><path class="w1idgzhlw"/><path class="jbukd8bpm"/></g></mask></defs><path mask="url(#SVGcfvsCdsn)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:anti-corrosion" {...props}></Icon>
