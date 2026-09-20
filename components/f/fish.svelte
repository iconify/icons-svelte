<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/nc1h4zb3b.css';
import '../../css/k/kxkkrtbdg.css';
import '../../css/j/jvue64i5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nc1h4zb3b"/><path class="kxkkrtbdg"/><path class="jvue64i5s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:fish" {...props}></Icon>
