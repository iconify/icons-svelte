<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaahlrc3c.css';
import '../../css/a/aqdf5vb7x.css';
import '../../css/d/d43wkrl0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qaahlrc3c"/><path class="aqdf5vb7x"/><path class="d43wkrl0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cherry-studio" {...props}></Icon>
