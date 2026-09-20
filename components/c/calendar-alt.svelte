<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irz5s5bib.css';
import '../../css/i/i6sdoobhw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irz5s5bib"/><path class="i6sdoobhw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:calendar-alt" {...props}></Icon>
